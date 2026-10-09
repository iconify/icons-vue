<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbfuulb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jbfuulb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-off-20-bold" /></template>
