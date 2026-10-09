<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh390wfyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oh390wfyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-20" /></template>
