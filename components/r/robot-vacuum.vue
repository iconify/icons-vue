<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3f6o9_to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3f6o9_to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:robot-vacuum" /></template>
