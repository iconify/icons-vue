<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e56w4s-6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e56w4s-6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:spray-can" /></template>
