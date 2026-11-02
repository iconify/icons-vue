<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubvbjccir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubvbjccir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mars-stroke-fill" /></template>
