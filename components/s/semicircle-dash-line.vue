<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u73ya1bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u73ya1bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:semicircle-dash-line" /></template>
