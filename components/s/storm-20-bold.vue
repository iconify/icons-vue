<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_vfm6cfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r_vfm6cfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:storm-20-bold" /></template>
