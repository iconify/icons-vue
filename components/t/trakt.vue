<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrco7s7xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rrco7s7xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:trakt" /></template>
