<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa1vadc0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa1vadc0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartwatch-x" /></template>
