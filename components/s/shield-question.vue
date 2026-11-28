<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jase8vblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jase8vblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shield-question" /></template>
