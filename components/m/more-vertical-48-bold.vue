<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh0yh6tgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rh0yh6tgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:more-vertical-48-bold" /></template>
