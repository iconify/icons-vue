<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th-l21bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="th-l21bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-map-coordinate" /></template>
