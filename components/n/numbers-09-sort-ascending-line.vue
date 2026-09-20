<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utmtt8oqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utmtt8oqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:numbers-09-sort-ascending-line" /></template>
