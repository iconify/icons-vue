<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcc7ulb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcc7ulb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moment-line" /></template>
