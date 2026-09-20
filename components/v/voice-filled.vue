<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e394lrbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e394lrbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:voice-filled" /></template>
