<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa-r_c5vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wa-r_c5vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nested" /></template>
