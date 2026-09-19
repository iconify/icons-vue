<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggiu84btg.css';
import '../../css/l/lwi--_w_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ggiu84btg"/><path class="lwi--_w_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-tag" /></template>
