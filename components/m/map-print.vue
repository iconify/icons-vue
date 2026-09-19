<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r85c85bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="r85c85bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-print" /></template>
