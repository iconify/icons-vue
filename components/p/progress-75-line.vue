<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r63g9jbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r63g9jbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:progress-75-line" /></template>
