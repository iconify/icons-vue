<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i16eiwdlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i16eiwdlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:spinner" /></template>
