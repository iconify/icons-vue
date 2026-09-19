<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njajxabqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="njajxabqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-magnifying-glass" /></template>
