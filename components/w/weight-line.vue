<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akiv3lb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akiv3lb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:weight-line" /></template>
