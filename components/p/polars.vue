<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x45ui7-ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x45ui7-ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:polars" /></template>
