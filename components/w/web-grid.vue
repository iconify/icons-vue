<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yawc-nbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yawc-nbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:web-grid" /></template>
