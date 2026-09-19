<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8lr8p0he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u8lr8p0he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:smaller-small" /></template>
