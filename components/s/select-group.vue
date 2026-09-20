<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfro8_bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfro8_bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:select-group" /></template>
