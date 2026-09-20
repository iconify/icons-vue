<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah7geomkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":273};
const content = `<path class="ah7geomkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nhost" /></template>
