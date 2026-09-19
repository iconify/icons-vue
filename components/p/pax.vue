<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nulwh4rnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nulwh4rnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pax" /></template>
