<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re1bh2b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re1bh2b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:projector-screen-line" /></template>
