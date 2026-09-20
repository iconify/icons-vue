<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uff_9unyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uff_9unyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:number-1" /></template>
