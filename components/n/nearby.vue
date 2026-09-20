<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7pid-56f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nearby" /></template>
<style>
.o7pid-56f {
  fill: currentColor;
  d: path("M12 16.4L7.6 12L12 7.6l4.4 4.4zm1.4 4.975q-.275.275-.65.425t-.75.15t-.75-.15t-.65-.425L2.625 13.4q-.275-.275-.425-.65T2.05 12t.15-.75t.425-.65l7.95-7.95q.3-.3.663-.45T12 2.05t.762.15t.663.45l7.95 7.95q.275.275.425.65t.15.75t-.15.75t-.425.65zM12 19.2l7.2-7.2L12 4.8L4.8 12z");
}

</style>
