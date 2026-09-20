<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw22crb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw22crb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:trash-alt" /></template>
