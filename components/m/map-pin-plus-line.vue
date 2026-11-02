<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lidt02l6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lidt02l6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-plus-line" /></template>
