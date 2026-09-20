<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ugmubyk.css';
import '../../css/c/cuvwpsbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ugmubyk"/><path class="cuvwpsbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:push-notification-alert-1" /></template>
