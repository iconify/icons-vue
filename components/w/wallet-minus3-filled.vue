<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq1lalb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq1lalb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wallet-minus3-filled" /></template>
