<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb_9esbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb_9esbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sparkling-2-line" /></template>
