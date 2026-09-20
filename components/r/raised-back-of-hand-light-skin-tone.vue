<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pj8o6l6dh"/><path class="czm5o1e5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:raised-back-of-hand-light-skin-tone" /></template>
<style>
.czm5o1e5j {
  fill: var(--svg-color--f7dece, #f7dece);
  d: path("M4.625 16.219c1.381-.611 3.354.208 4.75 2.188c.917 1.3 1.187 3.151 2.391 3.344c.46.073 1.234-.313 1.234-1.397V4.5s0-2 2-2s2 2 2 2v11.633c0-.029 1-.064 1-.082V2s0-2 2-2s2 2 2 2v14.053c0 .017 1 .041 1 .069V4.25s0-2 2-2s2 2 2 2v12.638c0 .118 1 .251 1 .398V8.75s0-2 2-2s2 2 2 2V24c0 6.627-5.373 12-12 12c-4.775 0-8.06-2.598-9.896-5.292C8.547 28.423 8.096 26.051 8 25.334c0 0-.123-1.479-1.156-2.865a58 58 0 0 0-3.125-3.866c-.317-.359-.625-1.707.906-2.384");
}

.pj8o6l6dh {
  fill: var(--svg-color--e0aa94, #e0aa94);
  d: path("M15.5 2.965a2.5 2.5 0 0 1 2.5 2.5v.005L20.5.465a2.5 2.5 0 0 1 2.5 2.5V4.25l2.5-1.535a2.5 2.5 0 0 1 2.5 2.5V8.75L29 18H15.458z");
}

</style>
