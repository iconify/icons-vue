<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1pk1--fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="o1pk1--fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map" /></template>
