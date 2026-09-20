<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxcqzcc_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxcqzcc_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tomi" /></template>
