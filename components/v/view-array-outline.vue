<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqhs8d5-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqhs8d5-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-array-outline" /></template>
