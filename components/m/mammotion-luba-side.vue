<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj-gdebvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj-gdebvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mammotion-luba-side" /></template>
