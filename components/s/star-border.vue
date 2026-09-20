<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqf1fgczx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqf1fgczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-border" /></template>
