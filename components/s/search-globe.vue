<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx9blzb3a.css';
import '../../css/i/iabrmvfcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="mx9blzb3a"/><path class="iabrmvfcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-globe" /></template>
