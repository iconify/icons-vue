<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-v5uabwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-v5uabwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motorbike-off" /></template>
