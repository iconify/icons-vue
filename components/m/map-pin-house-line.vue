<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itwsnnbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itwsnnbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-house-line" /></template>
