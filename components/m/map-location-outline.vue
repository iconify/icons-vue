<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7qn6rb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u7qn6rb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:map-location-outline" /></template>
