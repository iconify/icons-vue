<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr3ylkbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr3ylkbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:percentage-line" /></template>
