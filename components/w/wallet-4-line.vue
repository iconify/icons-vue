<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyoulr1uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyoulr1uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-4-line" /></template>
