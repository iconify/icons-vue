<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr812zbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr812zbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:time-duration-line" /></template>
