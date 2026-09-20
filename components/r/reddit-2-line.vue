<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaotxmbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaotxmbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:reddit-2-line" /></template>
