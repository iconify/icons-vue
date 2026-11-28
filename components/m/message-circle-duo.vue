<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm28qqb4l.css';
import '../../css/q/q32xggl4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sm28qqb4l"/><path class="primary q32xggl4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-duo" /></template>
