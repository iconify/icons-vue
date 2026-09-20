<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqch13d3y.css';
import '../../css/h/hke-fq0-t.css';
import '../../css/a/ahp5hdczi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":299};
const content = `<defs><linearGradient id="SVGqJZyIdTu" x1="31.047%" x2="68.957%" y1="11.705%" y2="88.303%"><stop offset="0%" class="hqch13d3y"/><stop offset="100%" class="hke-fq0-t"/></linearGradient></defs><path fill="url(#SVGqJZyIdTu)" class="ahp5hdczi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:surrealdb" /></template>
