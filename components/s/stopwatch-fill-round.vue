<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcer7mbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcer7mbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stopwatch-fill-round" /></template>
