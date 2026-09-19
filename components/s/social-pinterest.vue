<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl3i8zbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="rl3i8zbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-pinterest" /></template>
