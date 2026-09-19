<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf39cbn8y.css';
import '../../css/u/uhsthdc5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yf39cbn8y"/><path class="uhsthdc5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-share-alt" /></template>
