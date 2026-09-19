<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjo89vpyj.css';
import '../../css/l/lja1fl8ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="gjo89vpyj"/><path class="lja1fl8ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-data" /></template>
