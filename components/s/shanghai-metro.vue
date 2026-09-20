<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufs1ieqpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufs1ieqpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:shanghai-metro" /></template>
