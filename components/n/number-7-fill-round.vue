<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qawi-zbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qawi-zbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-7-fill-round" /></template>
