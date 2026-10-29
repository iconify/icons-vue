<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx-_h68tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx-_h68tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-solid" /></template>
