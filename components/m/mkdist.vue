<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gqzm6-r7o.css';
import '../../css/r/rvmgymbhx.css';
import '../../css/w/wtvxrsbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gqzm6-r7o"/><path class="rvmgymbhx"/><path class="wtvxrsbxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="unjs:mkdist" /></template>
