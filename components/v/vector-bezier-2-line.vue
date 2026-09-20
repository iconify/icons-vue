<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga2dxowpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga2dxowpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-bezier-2-line" /></template>
