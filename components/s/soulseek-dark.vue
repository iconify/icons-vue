<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f40n46bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f40n46bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:soulseek-dark" /></template>
