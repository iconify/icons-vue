<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r08hwea-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r08hwea-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:slider-horizontal-20" /></template>
