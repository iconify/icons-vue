<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlony8hhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlony8hhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:warm-up-3-line" /></template>
