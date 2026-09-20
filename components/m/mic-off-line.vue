<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywq4k-80h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywq4k-80h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-off-line" /></template>
