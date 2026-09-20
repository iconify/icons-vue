<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dapcy-r5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:musical-note" /></template>
<style>
.dapcy-r5p {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M34.209.206L11.791 2.793C10.806 2.907 10 3.811 10 4.803v18.782A7.9 7.9 0 0 0 7 23c-3.865 0-7 2.685-7 6s3.135 6 7 6s7-2.686 7-6V10.539l18-2.077v13.124A7.9 7.9 0 0 0 29 21c-3.865 0-7 2.685-7 6s3.135 6 7 6s7-2.686 7-6V1.803c0-.992-.806-1.71-1.791-1.597");
}

</style>
