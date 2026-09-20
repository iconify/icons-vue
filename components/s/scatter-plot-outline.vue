<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka6dq8sfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka6dq8sfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scatter-plot-outline" /></template>
