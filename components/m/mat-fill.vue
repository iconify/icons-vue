<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g83m5gbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g83m5gbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mat-fill" /></template>
