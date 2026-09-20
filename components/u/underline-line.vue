<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mppn_0eij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mppn_0eij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:underline-line" /></template>
