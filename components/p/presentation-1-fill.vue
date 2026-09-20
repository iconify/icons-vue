<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7sr6ib-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ib-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-1-fill" /></template>
