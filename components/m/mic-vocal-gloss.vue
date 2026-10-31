<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv2qxwlwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv2qxwlwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mic-vocal-gloss" /></template>
