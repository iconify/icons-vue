<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grfofuzaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grfofuzaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:paw" /></template>
