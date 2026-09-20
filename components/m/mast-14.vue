<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhb58tbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nhb58tbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:mast-14" /></template>
