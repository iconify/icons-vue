<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xooecg6hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xooecg6hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:third-stage" /></template>
