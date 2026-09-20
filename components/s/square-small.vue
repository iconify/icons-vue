<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfa-k33er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfa-k33er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-small" /></template>
