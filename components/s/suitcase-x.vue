<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sou8e1b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sou8e1b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:suitcase-x" /></template>
