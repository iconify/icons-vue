<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp8-iy64m.css';
import '../../css/h/h1_6ehjfr.css';
import '../../css/g/g_73anbpq.css';
import '../../css/h/hrzr1dobv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="hp8-iy64m"/><path class="h1_6ehjfr"/><g id="SVGTYOZ09iF"><path class="g_73anbpq"/><path class="hrzr1dobv"/></g><use width="100%" height="100%" href="#SVGTYOZ09iF" transform="matrix(-1 0 0 1 640 0)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mo-4x3" /></template>
