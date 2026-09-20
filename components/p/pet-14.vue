<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1hbegbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q1hbegbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:pet-14" /></template>
