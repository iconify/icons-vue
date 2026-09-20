<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gos5wfb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gos5wfb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-star" /></template>
