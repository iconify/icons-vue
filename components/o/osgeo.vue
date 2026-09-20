<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewr23_bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewr23_bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:osgeo" /></template>
