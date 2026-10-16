<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0-l2la1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f0-l2la1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sandstorm-20" /></template>
