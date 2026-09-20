<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfvy4itsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfvy4itsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:number-9" /></template>
