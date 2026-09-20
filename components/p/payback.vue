<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytrf_vbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytrf_vbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:payback" /></template>
