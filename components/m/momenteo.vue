<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8m2zvbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8m2zvbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:momenteo" /></template>
