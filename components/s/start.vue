<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/una8nxqty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="una8nxqty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:start" /></template>
