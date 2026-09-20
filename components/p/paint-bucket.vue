<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtpwcbrvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtpwcbrvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:paint-bucket" /></template>
