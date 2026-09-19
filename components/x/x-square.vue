<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdzp8acbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdzp8acbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:x-square" /></template>
