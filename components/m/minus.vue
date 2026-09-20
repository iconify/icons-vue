<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9s0nbbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="j9s0nbbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:minus" /></template>
