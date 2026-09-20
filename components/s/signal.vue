<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro1ry2bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro1ry2bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:signal" /></template>
