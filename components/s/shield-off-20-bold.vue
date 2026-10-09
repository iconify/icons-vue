<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj2wnyv8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dj2wnyv8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-off-20-bold" /></template>
