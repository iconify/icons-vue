<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urbubkvgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urbubkvgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sticky-note-add-fill" /></template>
