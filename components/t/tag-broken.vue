<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iar3qwbrm.css';
import '../../css/e/epme-tb1k.css';
import '../../css/a/af-qgnuco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iar3qwbrm"/><path class="epme-tb1k"/><path class="af-qgnuco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-broken" /></template>
