<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzl-74xew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzl-74xew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:paint-roller" /></template>
