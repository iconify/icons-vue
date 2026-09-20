<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcsg_ybgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcsg_ybgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-socket-singapore" /></template>
