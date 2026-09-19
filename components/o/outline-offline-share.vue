<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im5a89lao"/><path class="nkdfj9b2n"/><path class="k1psf2qsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-offline-share" /></template>
<style>
.im5a89lao {
  fill: currentColor;
  d: path("M6 5H4v16c0 1.1.9 2 2 2h10v-2H6z");
}

.k1psf2qsp {
  fill: currentColor;
  d: path("M12.5 10.25h1.63l-.69.69L14.5 12L17 9.5L14.5 7l-1.06 1.06l.69.69H12c-.55 0-1 .45-1 1V12h1.5z");
}

.nkdfj9b2n {
  fill: currentColor;
  d: path("M18 1h-8c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16h-8v-1h8zm0-3h-8V6h8zm0-10h-8V3h8z");
}

</style>
