<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crjh0zb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crjh0zb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:yuanbao-line" /></template>
