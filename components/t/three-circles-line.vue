<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciftksbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciftksbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:three-circles-line" /></template>
