<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l07pnbbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l07pnbbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:speech-bubble-question" /></template>
