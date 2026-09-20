<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd4f1zkyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wd4f1zkyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:peertube-fill-24" /></template>
