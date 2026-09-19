<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2zmswy-h.css';
import '../../css/q/q6tuz1lwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m2zmswy-h"/><path class="q6tuz1lwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:screen-mag" /></template>
