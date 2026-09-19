<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_3k-myyj.css';
import '../../css/i/i1nctz7rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_3k-myyj"/><path class="i1nctz7rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:pie-chart-1" /></template>
