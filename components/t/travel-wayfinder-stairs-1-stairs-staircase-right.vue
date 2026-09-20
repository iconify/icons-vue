<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aljnsoips.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="aljnsoips"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-wayfinder-stairs-1-stairs-staircase-right" /></template>
