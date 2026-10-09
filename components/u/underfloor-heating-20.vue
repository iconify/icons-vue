<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzmkpsb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yzmkpsb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underfloor-heating-20" /></template>
