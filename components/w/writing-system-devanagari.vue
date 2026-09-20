<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txxr3r77k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txxr3r77k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:writing-system-devanagari" /></template>
