<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1pun8bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1pun8bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-chevron-down" /></template>
