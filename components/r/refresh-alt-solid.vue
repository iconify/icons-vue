<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnnunc8ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnnunc8ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:refresh-alt-solid" /></template>
