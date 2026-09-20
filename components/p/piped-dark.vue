<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f09tprafk.css';
import '../../css/u/ug7q-clry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f09tprafk"/><path class="ug7q-clry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piped-dark" /></template>
