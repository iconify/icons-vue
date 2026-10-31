<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbbwzybbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbbwzybbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-side-fill-round" /></template>
