<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwfi32n6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwfi32n6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-3-line" /></template>
