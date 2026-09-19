<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x65shebem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="x65shebem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:step" /></template>
