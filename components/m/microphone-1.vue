<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbcv2ibqv.css';
import '../../css/q/q9u93xp0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbcv2ibqv"/><path class="q9u93xp0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:microphone-1" /></template>
