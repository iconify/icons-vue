<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlvshwb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="nlvshwb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:twig" /></template>
