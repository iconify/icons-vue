<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duab7-boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duab7-boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-9-plus-box" /></template>
