<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwd01r-qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwd01r-qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-unfold-4-fill" /></template>
