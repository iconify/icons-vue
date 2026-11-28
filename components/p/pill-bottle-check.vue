<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz7r0yydl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz7r0yydl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pill-bottle-check" /></template>
