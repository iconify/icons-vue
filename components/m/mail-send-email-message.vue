<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u87k-tmdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u87k-tmdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:mail-send-email-message" /></template>
