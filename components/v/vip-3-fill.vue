<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv4yjtbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv4yjtbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-3-fill" /></template>
