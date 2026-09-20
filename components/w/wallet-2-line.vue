<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nax9wcbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nax9wcbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-2-line" /></template>
