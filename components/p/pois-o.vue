<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln_xg1opz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ln_xg1opz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:pois-o" /></template>
