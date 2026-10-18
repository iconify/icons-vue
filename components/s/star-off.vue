<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj2od2bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj2od2bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:star-off" /></template>
