<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf_j2_b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lf_j2_b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scis-control-tower" /></template>
