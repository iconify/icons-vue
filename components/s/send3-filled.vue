<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws503nztc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws503nztc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:send3-filled" /></template>
