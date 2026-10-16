<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mil3nlbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mil3nlbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plane-takeoff-20-bold" /></template>
