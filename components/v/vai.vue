<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g376v7bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g376v7bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vai" /></template>
