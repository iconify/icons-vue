<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3-kin2ph.css';
import '../../css/q/q6tuz1lwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="y3-kin2ph"/><path class="q6tuz1lwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:screen-mag-o" /></template>
