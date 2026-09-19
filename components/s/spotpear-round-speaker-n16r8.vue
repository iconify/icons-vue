<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okzh9cbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okzh9cbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:spotpear-round-speaker-n16r8" /></template>
