<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdnn1hg-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdnn1hg-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-bezier-2-line" /></template>
