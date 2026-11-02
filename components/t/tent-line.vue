<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voc_w8mff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voc_w8mff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tent-line" /></template>
