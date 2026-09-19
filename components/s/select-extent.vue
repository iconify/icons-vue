<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhwv4f-bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vhwv4f-bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:select-extent" /></template>
