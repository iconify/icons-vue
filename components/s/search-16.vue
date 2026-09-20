<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hya1gml3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hya1gml3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:search-16" /></template>
