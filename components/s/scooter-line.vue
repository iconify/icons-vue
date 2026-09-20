<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4_3rfb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4_3rfb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scooter-line" /></template>
