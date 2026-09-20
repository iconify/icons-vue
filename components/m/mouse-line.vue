<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnnafxxnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnnafxxnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mouse-line" /></template>
