<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz92cqnqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz92cqnqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:y-skew-line" /></template>
