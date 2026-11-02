<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzumz54ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzumz54ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-plus-line" /></template>
