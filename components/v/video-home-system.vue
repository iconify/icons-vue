<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrrjxl14w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrrjxl14w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-home-system" /></template>
