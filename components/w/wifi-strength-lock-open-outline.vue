<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgbn20iyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgbn20iyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-lock-open-outline" /></template>
