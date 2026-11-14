<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="doar3obut"/><path class="ueo3y70mw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-download" /></template>
<style>
.doar3obut {
  d: path("M8.5 2.5h4A1.5 1.5 0 0 1 14 4v8a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 7 12V4a1.5 1.5 0 0 1 1.5-1.5Z");
}

.ueo3y70mw {
  d: path("M4.5 10.5q0 .147.007.294q.007.148.022.294q.014.147.036.292q.022.146.05.291q.029.144.065.287t.078.284t.093.279q.049.139.106.275t.119.269t.132.263t.146.257q.075.126.157.248q.082.123.17.241q.087.119.181.232q.093.114.192.223t.203.214q.105.104.214.203t.223.192t.232.181t.241.17t.248.157q.127.076.257.146t.263.132t.269.119t.275.106t.279.093q.141.042.284.078t.287.065q.145.028.291.05q.145.022.292.036q.146.015.294.022q.147.007.294.007q.337 0 .672-.038q.335-.037.663-.112q.329-.075.647-.187q.318-.111.622-.257q.303-.147.589-.326q.285-.179.548-.389t.502-.449q.238-.238.449-.502m1.185-2.531q.123-.598.123-1.209m-6 6v4m-3 0H13m5-6v7m-3-3l3 3l3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
