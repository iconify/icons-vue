<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ityz56bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ityz56bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:thermometer-internal" /></template>
