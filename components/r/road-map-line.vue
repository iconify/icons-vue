<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_e50ql6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_e50ql6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:road-map-line" /></template>
