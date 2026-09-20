<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez8rbaciu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ez8rbaciu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-backpack-walking-with-hiking-pole-in-gable-roofed-shelter" /></template>
