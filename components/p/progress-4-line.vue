<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipte8ubfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipte8ubfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-4-line" /></template>
