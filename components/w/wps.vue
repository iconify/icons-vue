<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6c33xzwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="t6c33xzwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:wps" /></template>
