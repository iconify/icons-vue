<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpsu5qafs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpsu5qafs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scorpio-line" /></template>
