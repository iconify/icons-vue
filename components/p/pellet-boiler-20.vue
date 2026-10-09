<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxjtvuboi.css';
import '../../css/p/pzrdwd7sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mxjtvuboi"/><path class="pzrdwd7sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pellet-boiler-20" /></template>
