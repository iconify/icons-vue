<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f43t98_ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f43t98_ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinterest-light" /></template>
