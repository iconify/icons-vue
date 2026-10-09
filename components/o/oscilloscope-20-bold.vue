<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgdmwwbvt.css';
import '../../css/j/jk8gvlbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rgdmwwbvt"/><path class="jk8gvlbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oscilloscope-20-bold" /></template>
