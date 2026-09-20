<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdyz09b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdyz09b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quarter-circle-dash-fill" /></template>
