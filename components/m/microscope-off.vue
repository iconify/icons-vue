<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yybb-b7zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microscope-off" /></template>
<style>
.yybb-b7zz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.6v-.1h4v4.1m-1.9 5.9H6.5v-2.1m4-3.9H12q.147 0 .294.007q.148.007.294.022q.147.014.292.036q.146.022.291.05q.144.029.287.065t.284.078t.279.093q.139.049.275.106t.269.119t.263.132t.257.146q.126.075.248.157q.123.082.241.17q.119.087.232.181q.114.093.223.192t.214.203q.104.105.203.214t.192.223q.094.113.181.232q.088.118.17.241q.082.122.157.248q.076.127.146.257t.132.263t.119.269t.106.275q.05.138.093.279t.078.284q.036.143.065.287q.028.145.05.291q.022.145.036.292q.015.146.022.294q.007.147.007.294q0 .685-.154 1.352m-3.664 4.237Q13.13 18.5 12 18.5V21m-5.5 0h10.6M3.5 3.5l17 17");
}

</style>
