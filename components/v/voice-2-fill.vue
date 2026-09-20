<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_xbbgirr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_xbbgirr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:voice-2-fill" /></template>
