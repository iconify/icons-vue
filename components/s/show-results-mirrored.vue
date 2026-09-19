<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq1y5xbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oq1y5xbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:show-results-mirrored" /></template>
