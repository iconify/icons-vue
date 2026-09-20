<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yodhlsb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yodhlsb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:network-error-line" /></template>
