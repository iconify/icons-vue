<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1h9j1hcr.css';
import '../../css/y/y497hebmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s1h9j1hcr"/><path class="y497hebmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zero-emissions-20-bold" /></template>
