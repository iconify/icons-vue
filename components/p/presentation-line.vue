<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc15d8b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc15d8b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:presentation-line" /></template>
