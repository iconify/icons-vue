<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptga7ebrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ptga7ebrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-agelimit-9" /></template>
