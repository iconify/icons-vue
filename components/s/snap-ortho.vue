<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c881r6e3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="c881r6e3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:snap-ortho" /></template>
