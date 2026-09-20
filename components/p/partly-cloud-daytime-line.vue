<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzh4x-bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzh4x-bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:partly-cloud-daytime-line" /></template>
