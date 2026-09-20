<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvq731b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvq731b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-calendar-light" /></template>
