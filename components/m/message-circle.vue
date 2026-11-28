<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q32xggl4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q32xggl4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle" /></template>
