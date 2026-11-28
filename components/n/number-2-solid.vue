<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da1bw8ugd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da1bw8ugd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-2-solid" /></template>
