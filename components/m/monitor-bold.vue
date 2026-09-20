<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr0hlbc2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr0hlbc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:monitor-bold" /></template>
