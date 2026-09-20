<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1p_9ubql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1p_9ubql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pan-left" /></template>
