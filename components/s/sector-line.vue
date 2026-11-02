<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzl1hcbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzl1hcbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sector-line" /></template>
