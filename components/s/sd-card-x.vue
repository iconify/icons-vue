<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfl8bdbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfl8bdbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sd-card-x" /></template>
