<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi5-4wclt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi5-4wclt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sticky-note-x" /></template>
