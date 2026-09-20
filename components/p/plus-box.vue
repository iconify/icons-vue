<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt50iobdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt50iobdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:plus-box" /></template>
