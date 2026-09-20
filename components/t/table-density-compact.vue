<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2v24ccdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h2v24ccdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:table-density-compact" /></template>
