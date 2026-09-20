<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zapfc8g7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zapfc8g7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-outline-filled" /></template>
