<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o88ykrvvz.css';
import '../../css/w/wwhsvn6bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="o88ykrvvz"/><circle class="wwhsvn6bz"/><polyline points="6.25 12 6.25 2.75 14.25 1.75 14.25 11"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:music" /></template>
