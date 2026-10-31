<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjat-_exd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjat-_exd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-fill-round" /></template>
