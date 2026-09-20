<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veig2p99j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veig2p99j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mastercard-line" /></template>
