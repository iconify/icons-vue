<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xln1ps8-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xln1ps8-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:train" /></template>
