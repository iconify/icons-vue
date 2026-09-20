<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7g_t9lqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7g_t9lqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motorbike-electric" /></template>
