<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yic6p8mfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yic6p8mfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:star-solid-expressive" /></template>
