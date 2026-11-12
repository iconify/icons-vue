<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbk0qrbla.css';
import '../../css/l/l3azjz_az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbk0qrbla"/><path class="l3azjz_az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:saltcorn-dark" /></template>
