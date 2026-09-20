<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je12_vbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je12_vbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shark-off" /></template>
