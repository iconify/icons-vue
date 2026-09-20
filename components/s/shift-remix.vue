<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipv-ywb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ipv-ywb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shift-remix" /></template>
