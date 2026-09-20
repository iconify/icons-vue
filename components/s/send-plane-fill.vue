<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5k4a-bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5k4a-bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:send-plane-fill" /></template>
