<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syxhos6-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syxhos6-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:microphone-cancelled-filled" /></template>
