<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8zrl8s0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8zrl8s0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:redo-stroke-alt" /></template>
