<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngrcr4m5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngrcr4m5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:siri-frame-fill" /></template>
