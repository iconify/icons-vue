<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwiaqi-vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwiaqi-vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:module-puzzle-2" /></template>
