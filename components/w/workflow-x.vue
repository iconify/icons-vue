<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7_y0l8bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7_y0l8bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:workflow-x" /></template>
