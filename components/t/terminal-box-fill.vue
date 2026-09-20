<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-kj4x7ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-kj4x7ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-box-fill" /></template>
