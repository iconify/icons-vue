<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzhcoetij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzhcoetij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:prescription-line" /></template>
