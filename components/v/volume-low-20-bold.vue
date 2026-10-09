<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrjlwqjtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jrjlwqjtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-low-20-bold" /></template>
