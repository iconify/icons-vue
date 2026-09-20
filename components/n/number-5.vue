<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd-tiu1yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd-tiu1yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:number-5" /></template>
