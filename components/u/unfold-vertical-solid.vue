<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4l0_wrne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4l0_wrne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:unfold-vertical-solid" /></template>
