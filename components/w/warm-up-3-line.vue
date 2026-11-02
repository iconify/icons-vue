<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryrab4nvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryrab4nvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:warm-up-3-line" /></template>
