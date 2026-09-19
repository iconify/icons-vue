<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih837srtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih837srtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:plejd" /></template>
