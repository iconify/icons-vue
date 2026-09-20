<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cypzkkbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cypzkkbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-agelimit-6" /></template>
