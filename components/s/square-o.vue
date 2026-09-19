<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8dod733a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="n8dod733a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:square-o" /></template>
