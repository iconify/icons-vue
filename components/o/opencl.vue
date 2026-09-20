<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2_gytbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r2_gytbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:opencl" /></template>
