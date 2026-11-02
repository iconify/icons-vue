<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7o5_04oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7o5_04oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-warning-line" /></template>
