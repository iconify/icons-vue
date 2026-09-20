<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a538odb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-off-32-filled" /></template>
<style>
.a538odb6x {
  fill: currentColor;
  d: path("m20.923 22.337l7.37 7.37a1 1 0 0 0 1.414-1.414l-26-26a1 1 0 0 0-1.414 1.414L4.884 6.3A4.5 4.5 0 0 0 2 10.5v11A4.5 4.5 0 0 0 6.5 26h10c2.2 0 4.03-1.578 4.423-3.663m1.577-3.374l5.52 5.519c1.056-.134 1.976-1.017 1.976-2.236V9.754c0-1.814-2.036-2.882-3.528-1.852l-3.968 2.74zM9.537 6L21 17.463V10.5A4.5 4.5 0 0 0 16.5 6z");
}

</style>
