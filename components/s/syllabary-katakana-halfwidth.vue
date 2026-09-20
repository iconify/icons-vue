<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd-ebccqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd-ebccqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:syllabary-katakana-halfwidth" /></template>
