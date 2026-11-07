<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0sedyn1y.css';
import '../../css/x/x0zzi0bor.css';
import '../../css/n/nh75w0b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0sedyn1y"/><path class="x0zzi0bor"/><path class="nh75w0b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-graph-outline" /></template>
