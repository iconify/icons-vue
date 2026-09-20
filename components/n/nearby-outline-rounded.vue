<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwcc9ibix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nearby-outline-rounded" /></template>
<style>
.iwcc9ibix {
  fill: currentColor;
  d: path("m11.3 15.7l-3-3Q8 12.4 8 12t.3-.7l3-3q.3-.3.7-.3t.7.3l3 3q.3.3.3.7t-.3.7l-3 3q-.3.3-.7.3t-.7-.3m2.1 5.675q-.275.275-.65.425t-.75.15t-.75-.15t-.65-.425L2.625 13.4q-.275-.275-.425-.65T2.05 12t.15-.75t.425-.65l7.95-7.95q.3-.3.663-.45T12 2.05t.762.15t.663.45l7.95 7.95q.275.275.425.65t.15.75t-.15.75t-.425.65zM12 19.2l7.2-7.2L12 4.8L4.8 12z");
}

</style>
