<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unpd6qfsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="unpd6qfsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:wine-glass" /></template>
