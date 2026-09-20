<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mngos4sma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mngos4sma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:netease-cloud-music-line" /></template>
