<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3nheebop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="x3nheebop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:repeat-button" /></template>
