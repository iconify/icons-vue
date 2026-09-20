<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3wlv74so.css';
import '../../css/r/r1y0urzis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j3wlv74so"/><circle class="r1y0urzis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:network-off" /></template>
