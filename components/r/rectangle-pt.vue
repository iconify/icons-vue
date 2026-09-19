<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a89ywegkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="a89ywegkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:rectangle-pt" /></template>
