<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f97ienhes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f97ienhes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wrench" /></template>
