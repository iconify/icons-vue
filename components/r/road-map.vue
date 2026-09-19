<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8ued2b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="g8ued2b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:road-map" /></template>
