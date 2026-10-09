<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px_2uxb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="px_2uxb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pentagon-20-bold" /></template>
