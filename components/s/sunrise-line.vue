<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7yo8v4vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7yo8v4vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sunrise-line" /></template>
