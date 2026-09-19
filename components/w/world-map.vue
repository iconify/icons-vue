<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agt8pubkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="agt8pubkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:world-map" /></template>
