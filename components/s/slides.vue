<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5s9labbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5s9labbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:slides" /></template>
