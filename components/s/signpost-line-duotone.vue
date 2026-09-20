<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/idmd52b7b.css';
import '../../css/g/gqb61cbma.css';
import '../../css/c/c_criydpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="idmd52b7b"/><path class="gqb61cbma"/><path class="c_criydpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signpost-line-duotone" /></template>
