<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d74jwwb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d74jwwb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:oracle" /></template>
