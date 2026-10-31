<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh1w3bcxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh1w3bcxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telescope-fill-round" /></template>
