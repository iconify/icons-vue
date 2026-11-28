<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3z30qbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3z30qbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:redo" /></template>
