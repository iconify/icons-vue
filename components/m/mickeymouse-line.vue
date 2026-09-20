<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox68djqql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox68djqql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mickeymouse-line" /></template>
