<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdfzpcc-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdfzpcc-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mqtt-line" /></template>
