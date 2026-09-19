<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7cbxcbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="n7cbxcbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:refresh" /></template>
