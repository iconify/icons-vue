<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssnjoqlqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssnjoqlqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-line" /></template>
