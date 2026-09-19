<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5h7g2bhi"/><path class="s5uyc6bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mail" /></template>
<style>
.s5uyc6bty {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 2l-8 4.99L4 6zm0 12H4V8l8 5l8-5z");
}

.y5h7g2bhi {
  fill: currentColor;
  d: path("M20 6H4l8 4.99zM4 8v10h16V8l-8 5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
