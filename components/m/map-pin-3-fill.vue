<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygif3dzbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygif3dzbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-3-fill" /></template>
