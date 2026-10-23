<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuogiubpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuogiubpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tally-5" /></template>
