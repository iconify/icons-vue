<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7ipbbrfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":456};
const content = `<path class="q7ipbbrfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pin-account" /></template>
