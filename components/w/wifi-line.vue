<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye-q54bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye-q54bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wifi-line" /></template>
