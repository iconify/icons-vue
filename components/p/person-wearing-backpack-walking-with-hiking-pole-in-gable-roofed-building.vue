<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eowlsrbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eowlsrbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-backpack-walking-with-hiking-pole-in-gable-roofed-building" /></template>
