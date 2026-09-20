<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx1s9bc_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx1s9bc_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-2-line" /></template>
