<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zytt76bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zytt76bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-line" /></template>
