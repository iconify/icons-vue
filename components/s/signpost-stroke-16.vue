<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9khw75hp.css';
import '../../css/x/xaq4gjbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i9khw75hp"/><path class="xaq4gjbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:signpost-stroke-16" /></template>
