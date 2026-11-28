<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpoln0yba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoln0yba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shower" /></template>
