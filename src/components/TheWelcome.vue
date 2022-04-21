<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconLocation.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Vị trí</template>

    Đình Nội Lâu Thượng thuộc xã Trưng Vương - Thành phố Việt Trì - Tỉnh Phú Thọ.<br>

    Tại đây có 2 ngôi Đình làng lớn đó là Đình Nội thuộc địa phận Đội 6 Xóm Sải và Đình ngoại thuộc địa phận xóm Mai
    Đồi.<br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Giới Thiệu Về Di Tích</template>

    Lâu Thượng nghĩa là lầu phía trên.<br>

    Cả 2 ngôi đình cổ đều thuộc di tích Quốc gia.
  </WelcomeItem>

</template>
