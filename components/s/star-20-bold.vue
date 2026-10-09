<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uanbx55lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uanbx55lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-20-bold" /></template>
