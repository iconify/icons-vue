<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh8_-yihl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh8_-yihl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:receipt-off" /></template>
