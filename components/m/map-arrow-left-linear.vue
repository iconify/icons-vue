<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1723bvbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1723bvbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-left-linear" /></template>
