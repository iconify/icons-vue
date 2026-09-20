<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kt_iz7ykc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-mail-20-filled" /></template>
<style>
.kt_iz7ykc {
  fill: currentColor;
  d: path("M9 2a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-4.991 9A2 2 0 0 0 2 13c0 1.691.833 2.966 2.135 3.797C5.417 17.614 7.145 18 9 18v-5a2 2 0 0 1 1.996-2zm10.5 4.927l-4.496-2.623A1.5 1.5 0 0 1 11.5 12h6a1.5 1.5 0 0 1 1.5 1.5v.009zm.228 1.013L19 14.645V17.5a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5v-3.046l4.248 2.478a.5.5 0 0 0 .49.008");
}

</style>
