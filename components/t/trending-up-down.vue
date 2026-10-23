<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-qz8s0dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-qz8s0dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:trending-up-down" /></template>
