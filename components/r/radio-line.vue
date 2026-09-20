<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryh7p5bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryh7p5bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radio-line" /></template>
