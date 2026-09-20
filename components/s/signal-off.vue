<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f81esqb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f81esqb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:signal-off" /></template>
