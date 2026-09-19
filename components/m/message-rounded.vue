<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ingj11ljg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ingj11ljg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-rounded" /></template>
