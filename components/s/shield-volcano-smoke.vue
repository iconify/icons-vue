<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz1dhdcvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wz1dhdcvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:shield-volcano-smoke" /></template>
