<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmo9a1bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmo9a1bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:send-horizontal" /></template>
