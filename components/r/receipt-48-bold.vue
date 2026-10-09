<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk4s-jblr.css';
import '../../css/q/qftg15_vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qk4s-jblr"/><path class="qftg15_vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:receipt-48-bold" /></template>
