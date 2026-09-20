<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivro_3fld.css';
import '../../css/l/l6qh78cyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ivro_3fld"/><path class="l6qh78cyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:pie-chart" /></template>
