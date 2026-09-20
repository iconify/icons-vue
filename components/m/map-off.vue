<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z9gsdx3mg.css';
import '../../css/x/xn39h-g0p.css';
import '../../css/b/b8zhl9blw.css';
import '../../css/w/wewxyhbwh.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="z9gsdx3mg"/><path clip-rule="evenodd" class="xn39h-g0p"/><path clip-rule="evenodd" class="b8zhl9blw"/><path class="wewxyhbwh"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:map-off" /></template>
