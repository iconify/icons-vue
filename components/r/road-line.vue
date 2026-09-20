<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feqma1bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feqma1bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:road-line" /></template>
