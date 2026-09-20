<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzm_x0bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mzm_x0bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:skyshowtime-dark" /></template>
