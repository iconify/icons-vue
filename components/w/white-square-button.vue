<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nf04p9bnl"/><path class="qil8x6a3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:white-square-button" /></template>
<style>
.nf04p9bnl {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M127.56 113.88c0 7.53-6.16 13.69-13.69 13.69H14.12c-7.53 0-13.69-6.16-13.69-13.69V14.12C.43 6.59 6.59.43 14.12.43h99.75c7.53 0 13.69 6.16 13.69 13.69z");
}

.qil8x6a3g {
  fill: var(--svg-color--424242, #424242);
  d: path("M108.17 100.02c0 4.73-3.87 8.6-8.6 8.6H27.6c-4.73 0-8.6-3.87-8.6-8.6V28.05c0-4.73 3.87-8.6 8.6-8.6h71.97c4.73 0 8.6 3.87 8.6 8.6z");
}

</style>
