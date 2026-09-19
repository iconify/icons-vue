<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrn-ktbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrn-ktbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:send" /></template>
