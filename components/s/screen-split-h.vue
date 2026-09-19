<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaa3j5mot.css';
import '../../css/w/w0y1bnl1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="eaa3j5mot"/><path class="w0y1bnl1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:screen-split-h" /></template>
