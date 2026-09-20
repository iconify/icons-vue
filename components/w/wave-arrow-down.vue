<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fse5akbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fse5akbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wave-arrow-down" /></template>
