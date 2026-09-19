<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_47-0bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_47-0bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:share-2-thin" /></template>
