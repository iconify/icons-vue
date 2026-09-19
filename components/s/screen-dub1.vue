<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n689fv7bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="n689fv7bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:screen-dub1" /></template>
