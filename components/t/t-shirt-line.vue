<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtqa41btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtqa41btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:t-shirt-line" /></template>
