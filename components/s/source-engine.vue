<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k98pe1uop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k98pe1uop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:source-engine" /></template>
