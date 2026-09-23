<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/nxkqdkb5j.css';
import '../../css/n/nbau3hbls.css';
import '../../css/d/dmrlztban.css';
import '../../css/p/pfr5hhxja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nxkqdkb5j"/><path class="nbau3hbls"/><path class="dmrlztban"/><path class="pfr5hhxja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-sparkles-sharp-duotone" /></template>
