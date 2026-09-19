<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggiu84btg.css';
import '../../css/d/do6vm3bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ggiu84btg"/><path class="do6vm3bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-bookmark" /></template>
