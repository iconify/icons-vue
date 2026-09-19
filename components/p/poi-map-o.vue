<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq6a8xb0a.css';
import '../../css/o/okbbhw_ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="tq6a8xb0a"/><path class="okbbhw_ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:poi-map-o" /></template>
