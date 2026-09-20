<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyhihbcfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyhihbcfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pause-mini-fill" /></template>
