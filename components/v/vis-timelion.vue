<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4p90eukn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w4p90eukn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-timelion" /></template>
