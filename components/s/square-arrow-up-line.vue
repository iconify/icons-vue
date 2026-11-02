<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf1tdw8qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf1tdw8qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-arrow-up-line" /></template>
