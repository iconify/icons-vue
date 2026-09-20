<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd040sb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd040sb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:waves-birds" /></template>
