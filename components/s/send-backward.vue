<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx6vj_dxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx6vj_dxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:send-backward" /></template>
