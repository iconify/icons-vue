<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vczi7rbjb.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/g/grb3uxweq.css';
import '../../css/z/znam6bmtw.css';
import '../../css/m/mai4clilr.css';
import '../../css/m/mdve_fbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vczi7rbjb wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="grb3uxweq wm-k"/><path class="wm-a znam6bmtw"/><path class="mai4clilr wm-s"/><path class="mdve_fbzl wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:worried-blueprint" /></template>
