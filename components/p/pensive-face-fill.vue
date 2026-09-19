<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3kr0wb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3kr0wb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:pensive-face-fill" /></template>
