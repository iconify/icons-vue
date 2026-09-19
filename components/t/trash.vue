<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvfxynb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1536};
const content = `<path class="vvfxynb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:trash" /></template>
