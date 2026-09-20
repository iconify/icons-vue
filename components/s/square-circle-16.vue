<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy9tbfb-j.css';
import '../../css/p/pj07l70hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gy9tbfb-j"/><path class="pj07l70hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:square-circle-16" /></template>
