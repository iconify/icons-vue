<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hngr2_b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hngr2_b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-fill-round" /></template>
