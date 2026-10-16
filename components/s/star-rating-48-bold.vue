<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgjq70q0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rgjq70q0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-rating-48-bold" /></template>
