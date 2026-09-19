<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjmsf2bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hjmsf2bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pencil-paintbrush-outline" /></template>
