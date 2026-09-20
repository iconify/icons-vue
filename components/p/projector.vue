<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz34yrbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nz34yrbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:projector" /></template>
