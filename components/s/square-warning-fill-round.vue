<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl4t1zbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl4t1zbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-warning-fill-round" /></template>
