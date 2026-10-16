<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_nt8zixb.css';
import '../../css/r/r77s4pbmz.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g_nt8zixb"/><path class="r77s4pbmz"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vertical-solar-20" /></template>
