<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mw8ccub0a.css';
import '../../css/j/jzhpb3bqb.css';
import '../../css/q/q5ty2f3-s.css';
import '../../css/a/axclidckd.css';
import '../../css/h/hurtu1upa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mw8ccub0a"/><path class="jzhpb3bqb"/><path class="q5ty2f3-s"/><path class="axclidckd"/><path class="hurtu1upa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-notes-line-duotone" /></template>
