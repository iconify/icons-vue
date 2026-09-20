<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fupjxpble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fupjxpble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticky-note-edit-outline" /></template>
