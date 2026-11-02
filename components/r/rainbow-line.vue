<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myvz9sgsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myvz9sgsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rainbow-line" /></template>
