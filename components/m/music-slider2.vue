<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nexjmib3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nexjmib3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-slider2" /></template>
