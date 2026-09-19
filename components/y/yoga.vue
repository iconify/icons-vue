<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw054bb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw054bb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:yoga" /></template>
