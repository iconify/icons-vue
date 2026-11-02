<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2288-utt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2288-utt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:semicircle-dash-line" /></template>
