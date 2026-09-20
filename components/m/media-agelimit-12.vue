<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co215vb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co215vb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-agelimit-12" /></template>
