<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fram0bcsw.css';
import '../../css/o/oz54tcchs.css';
import '../../css/d/d4o8lobkk.css';
import '../../css/u/ux_xktusc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fram0bcsw"/><path class="oz54tcchs"/><path class="d4o8lobkk"/><path class="ux_xktusc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scales-48-bold" /></template>
