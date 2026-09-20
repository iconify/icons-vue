<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/oh053ab4q.css';
import '../../css/w/wl1f6ubih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="h01tyzbfu"><path class="oh053ab4q"/><path class="wl1f6ubih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:strawberry" /></template>
