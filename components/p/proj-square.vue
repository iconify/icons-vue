<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu89-tlog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="hu89-tlog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:proj-square" /></template>
