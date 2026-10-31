<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l79oz4g8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l79oz4g8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sliders-gloss" /></template>
