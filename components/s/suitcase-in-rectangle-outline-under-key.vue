<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu4gmzb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uu4gmzb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:suitcase-in-rectangle-outline-under-key" /></template>
