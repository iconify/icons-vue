<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbm8gfb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="jbm8gfb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:topography" /></template>
