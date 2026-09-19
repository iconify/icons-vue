<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhe1fhswa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhe1fhswa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-vertical-square-fill" /></template>
