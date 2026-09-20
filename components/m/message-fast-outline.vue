<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg9bjcbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg9bjcbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-fast-outline" /></template>
