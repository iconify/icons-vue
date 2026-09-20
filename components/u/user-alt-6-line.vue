<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/t/tla7g4mpv.css';
import '../../css/d/d4z8ksbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path clip-rule="evenodd" class="tla7g4mpv"/><path class="d4z8ksbxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:user-alt-6-line" /></template>
