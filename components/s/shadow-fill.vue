<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coe30gbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coe30gbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shadow-fill" /></template>
