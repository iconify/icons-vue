<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp2x8y2ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp2x8y2ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-09" /></template>
