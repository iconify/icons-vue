<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhevklbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhevklbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:twitter" /></template>
