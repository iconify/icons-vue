<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibfx2rwgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibfx2rwgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:polygon-fill" /></template>
