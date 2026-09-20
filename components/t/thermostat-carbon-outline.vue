<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2s09mo3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermostat-carbon-outline" /></template>
<style>
.b2s09mo3u {
  fill: currentColor;
  d: path("M11.401 20.654q-.295-.121-.537-.358l-7.16-7.16q-.237-.242-.358-.537T3.225 12t.121-.602t.358-.534l7.16-7.16q.242-.242.537-.36t.599-.12t.602.118t.535.36l7.16 7.16q.241.237.36.535q.118.298.118.602t-.118.599t-.36.538l-7.16 7.16q-.237.236-.535.357t-.602.121t-.599-.121m1.041-1.071l7.14-7.14q.155-.154.155-.443t-.154-.442l-7.14-7.14q-.154-.155-.443-.155t-.442.154l-7.14 7.14q-.155.155-.155.443t.154.442l7.14 7.14q.155.155.443.155t.442-.154M12 12");
}

</style>
