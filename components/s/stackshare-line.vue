<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl0xavbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl0xavbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stackshare-line" /></template>
