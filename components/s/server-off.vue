<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7-16vbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7-16vbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:server-off" /></template>
