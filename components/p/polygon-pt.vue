<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vey7tzb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vey7tzb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:polygon-pt" /></template>
