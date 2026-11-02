<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz-c0x2vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-c0x2vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ship-line" /></template>
