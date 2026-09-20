<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5dqrrb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5dqrrb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speed-mini-line" /></template>
