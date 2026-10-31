<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjs_si8ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjs_si8ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-double-left-fill-round" /></template>
