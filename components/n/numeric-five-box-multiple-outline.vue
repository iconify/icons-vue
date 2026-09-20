<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2ay67glx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2ay67glx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-five-box-multiple-outline" /></template>
