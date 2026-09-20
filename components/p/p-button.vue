<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r9rioofmx"/><path class="j8yjm2x4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:p-button" /></template>
<style>
.j8yjm2x4u {
  fill: var(--svg-color--fff, #fff);
  d: path("M11 9.496C11 7.992 11.896 7 13.496 7h5.665c4.703 0 8.191 2.944 8.191 7.52c0 4.67-3.617 7.48-8 7.48H16v5.479c0 1.6-1.024 2.496-2.4 2.496s-2.6-.897-2.6-2.496zM16 18h3.062c2.018 0 3.297-1.465 3.297-3.385s-1.279-3.392-3.297-3.392H16z");
}

.r9rioofmx {
  fill: var(--svg-color--269, #269);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
