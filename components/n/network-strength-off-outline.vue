<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyovyz5ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyovyz5ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-off-outline" /></template>
