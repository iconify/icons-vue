<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7wez5bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="x7wez5bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:poi-info" /></template>
