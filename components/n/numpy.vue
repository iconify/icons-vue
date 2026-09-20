<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfod9ygkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfod9ygkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:numpy" /></template>
