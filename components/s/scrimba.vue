<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aker38-pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aker38-pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:scrimba" /></template>
