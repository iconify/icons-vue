<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0k7v5bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="h0k7v5bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:zoom-out" /></template>
