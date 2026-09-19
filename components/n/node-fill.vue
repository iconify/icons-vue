<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxtq1wxot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxtq1wxot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:node-fill" /></template>
