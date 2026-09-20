<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f86a2l21j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f86a2l21j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-quality-sd" /></template>
