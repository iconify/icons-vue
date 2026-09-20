<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p068o5acv.css';
import '../../css/f/f-iag6myh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p068o5acv"/><path class="f-iag6myh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pic-line" /></template>
