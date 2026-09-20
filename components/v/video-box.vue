<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyrz0touf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyrz0touf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-box" /></template>
