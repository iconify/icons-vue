<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vy1ihcjll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-ad-off-20-regular" /></template>
<style>
.vy1ihcjll {
  fill: currentColor;
  d: path("m2.854 2.146l15 15a.5.5 0 0 1-.708.708l-1.269-1.27c-.395.263-.87.416-1.38.416h-9a2.5 2.5 0 0 1-2.5-2.5v-9c0-.51.153-.985.415-1.38L2.146 2.854a.5.5 0 1 1 .708-.708m12.292 13.707L10 10.707V12.5a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5v-4a.5.5 0 0 1 .5-.5h1.793l-1-1H3.997v7.5a1.5 1.5 0 0 0 1.5 1.5h9c.232 0 .452-.053.649-.147M5.293 6L4.144 4.851a1.5 1.5 0 0 0-.147.649V6zm3 3H6v3h3V9.707zm7.704-3H8.121l1 1h6.876v6.876l.976.975q.024-.173.024-.351V7H17V6h-.003v-.5a2.5 2.5 0 0 0-2.5-2.5h-9q-.18 0-.351.024L6.12 4h8.376a1.5 1.5 0 0 1 1.5 1.5z");
}

</style>
