<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u86-pacbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u86-pacbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:spy-fill" /></template>
