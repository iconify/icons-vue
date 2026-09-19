<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uav6kirzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uav6kirzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:notification-stroke-16" /></template>
