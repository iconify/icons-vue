<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osw0yxbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="osw0yxbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seedling-outline" /></template>
