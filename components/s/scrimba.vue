<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh4-i6bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh4-i6bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scrimba" /></template>
