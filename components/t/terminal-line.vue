<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-5j1ab6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-5j1ab6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-line" /></template>
