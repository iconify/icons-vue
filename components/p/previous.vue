<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl-_zwbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl-_zwbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:previous" /></template>
