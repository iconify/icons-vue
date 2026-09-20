<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww4ub9yah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww4ub9yah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-2-fill" /></template>
