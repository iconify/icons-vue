<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvr4grpue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvr4grpue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microphone-message-off" /></template>
