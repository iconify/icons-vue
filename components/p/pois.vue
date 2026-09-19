<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7muz-b4d.css';
import '../../css/l/l7pghdblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d7muz-b4d"/><path class="l7pghdblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:pois" /></template>
