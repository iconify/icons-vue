<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwmm88bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwmm88bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stopwatch-sync-outline" /></template>
