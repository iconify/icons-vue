<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rbgvac43m"/><path class="iw-5gvbzz"/><path class="a66o55jif"/><path class="astf8zvsv"/><path class="yac0flb5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wam" /></template>
<style>
.a66o55jif {
  fill: var(--svg-color--221e20, #221e20);
  d: path("M14.664 16.502H9.652l-.45-1.238c-.056-.151.057-.315.225-.337l5.63-.675c.203-.023.367.157.299.337zm-4.354-5.625L9.185 8.064H7.217a.28.28 0 0 0-.265.372l1.39 4.691l7.593-1.125l1.109-3.56a.28.28 0 0 0-.265-.378H14.81l-1.125 2.813l-.72-2.61a.28.28 0 0 0-.27-.203h-1.26a.28.28 0 0 0-.27.203zm-.561 3.656a.563.563 0 1 0 0-1.125a.563.563 0 0 0 0 1.125m3.111-.995a.562.562 0 1 1-1.125 0a.562.562 0 0 1 1.125 0m2.514-.411a.562.562 0 1 1-1.125 0a.562.562 0 0 1 1.125 0");
}

.astf8zvsv {
  fill: var(--svg-color--2e2720, #2e2720);
  d: path("M19.873 12a7.876 7.876 0 0 1-14.915 3.52a7.88 7.88 0 0 1-.126-6.793a.59.59 0 0 0-.112-.675c-.265-.27-.715-.208-.872.135A9 9 0 1 0 8.47 3.72a.54.54 0 0 0-.225.798a.604.604 0 0 0 .732.208A7.875 7.875 0 0 1 19.873 12");
}

.ft5dv1b6b {
  fill: none;
}

.iw-5gvbzz {
  fill: var(--svg-color--fcb501, #fcb501);
  d: path("M10.463 19.466a9 9 0 0 0 9-9c0-2.193-1.09-4.218-2.402-5.777c1.97 1.649 3.527 4.13 3.527 6.902a9 9 0 0 1-9 9c-2.773 0-5.253-1.558-6.901-3.527c1.563 1.311 3.577 2.402 5.776 2.402");
}

.rbgvac43m {
  fill: var(--svg-color--ffcd00, #ffcd00);
  d: path("M11.999 20.44a8.438 8.438 0 1 0 0-16.876a8.438 8.438 0 0 0 0 16.875");
}

.yac0flb5r {
  fill: var(--svg-color--2e2720, #2e2720);
  d: path("M7.105 5.828a.59.59 0 0 0 .14-.787a.534.534 0 0 0-.776-.14c-.488.38-.937.81-1.338 1.282a.534.534 0 0 0 .04.725c.241.242.64.209.865-.056a8 8 0 0 1 1.07-1.024");
}

</style>
