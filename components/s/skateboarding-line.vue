<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xicf-7g9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xicf-7g9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skateboarding-line" /></template>
