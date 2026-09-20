<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziro4ceni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ziro4ceni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:music-notes" /></template>
