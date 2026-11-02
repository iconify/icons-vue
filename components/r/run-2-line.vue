<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_amfe9of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_amfe9of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:run-2-line" /></template>
