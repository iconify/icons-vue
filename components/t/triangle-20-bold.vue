<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyy81ebvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fyy81ebvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:triangle-20-bold" /></template>
