<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1wn-cbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1wn-cbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:soup-pot-line" /></template>
