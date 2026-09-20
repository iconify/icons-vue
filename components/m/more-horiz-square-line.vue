<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_cyjh5hd.css';
import '../../css/r/r8bd01bug.css';
import '../../css/h/hsksr011x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n_cyjh5hd"><path class="r8bd01bug"/><path class="hsksr011x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-horiz-square-line" /></template>
