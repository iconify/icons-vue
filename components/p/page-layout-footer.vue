<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmuxh0buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmuxh0buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:page-layout-footer" /></template>
