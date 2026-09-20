<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbvgox5fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbvgox5fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ubuntu-fill" /></template>
