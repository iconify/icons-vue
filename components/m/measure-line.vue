<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1gavvj8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="u1gavvj8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:measure-line" /></template>
