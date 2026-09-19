<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phjcr-75y.css';
import '../../css/i/iqsh6wb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="phjcr-75y"/><path class="iqsh6wb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:offset" /></template>
