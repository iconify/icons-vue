<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dng7rgnyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dng7rgnyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-off-20" /></template>
