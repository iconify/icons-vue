<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htlsyzb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htlsyzb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticker-text" /></template>
