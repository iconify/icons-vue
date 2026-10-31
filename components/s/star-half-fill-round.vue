<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylmun4jqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylmun4jqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-half-fill-round" /></template>
