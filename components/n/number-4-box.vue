<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4s-skbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4s-skbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-4-box" /></template>
