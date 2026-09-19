<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8fiu01er.css';
import '../../css/x/xpeiq2kly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d8fiu01er"/><path class="xpeiq2kly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-star" /></template>
