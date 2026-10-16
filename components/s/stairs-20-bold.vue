<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dae20rb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dae20rb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stairs-20-bold" /></template>
