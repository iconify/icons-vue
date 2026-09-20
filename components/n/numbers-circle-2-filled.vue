<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uecyfgbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uecyfgbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-circle-2-filled" /></template>
