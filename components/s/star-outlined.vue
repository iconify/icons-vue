<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbgxo8jma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbgxo8jma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:star-outlined" /></template>
