<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm8y5cbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm8y5cbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:yahoo-fill" /></template>
