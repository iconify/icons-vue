<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xf-a91bde"/><path class="q0zx9pbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-bold" /></template>
<style>
.q0zx9pbvx {
  fill: currentColor;
  d: path("M20.128 11.143c0 5.05-4.058 9.143-9.064 9.143S2 16.192 2 11.143S6.058 2 11.064 2s9.064 4.093 9.064 9.143");
}

.xf-a91bde {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.82 19.7a1.77 1.77 0 0 1 1.9-1.917c.189.016.414.084.643.154l.066.02l.06.018c.211.063.42.126.58.212a1.786 1.786 0 0 1 .638 2.55c-.1.151-.255.307-.41.464l-.045.044l-.044.045c-.156.157-.31.313-.46.414a1.754 1.754 0 0 1-2.528-.643a3.3 3.3 0 0 1-.21-.585l-.018-.06l-.02-.067c-.07-.232-.137-.459-.153-.648");
}

</style>
