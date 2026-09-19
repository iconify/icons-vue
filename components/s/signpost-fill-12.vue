<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgxf4lblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pgxf4lblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:signpost-fill-12" /></template>
