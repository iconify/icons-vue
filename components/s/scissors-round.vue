<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dedt5kbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dedt5kbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scissors-round" /></template>
