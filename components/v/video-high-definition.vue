<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8_u2ackk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8_u2ackk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-high-definition" /></template>
