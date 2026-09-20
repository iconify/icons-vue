<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/texztqb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="texztqb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:valhalla-maps-dark" /></template>
