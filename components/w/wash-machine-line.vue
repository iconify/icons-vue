<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh9zybb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh9zybb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wash-machine-line" /></template>
