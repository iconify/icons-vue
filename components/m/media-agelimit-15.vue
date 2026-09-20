<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvn2jqbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvn2jqbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-agelimit-15" /></template>
