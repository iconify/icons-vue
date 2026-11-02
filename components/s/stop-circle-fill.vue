<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te9-7obsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te9-7obsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stop-circle-fill" /></template>
