<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xr4ydkmqz.css';
import '../../css/g/ghf43lb4p.css';
import '../../css/s/sgq0p14ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xr4ydkmqz"/><path class="ghf43lb4p"/><circle class="sgq0p14ld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-fill-add" /></template>
