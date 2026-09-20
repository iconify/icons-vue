<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbsm2xwlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbsm2xwlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mailbox" /></template>
