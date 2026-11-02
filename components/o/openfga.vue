<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxs7g9ljm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":463,"height":463};
const content = `<path class="sxs7g9ljm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openfga" /></template>
