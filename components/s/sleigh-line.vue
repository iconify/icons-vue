<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7vydnbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7vydnbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sleigh-line" /></template>
