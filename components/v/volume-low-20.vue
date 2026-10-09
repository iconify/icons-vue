<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmzaum9qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fmzaum9qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-low-20" /></template>
