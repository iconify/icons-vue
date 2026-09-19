<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiimmlbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oiimmlbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:rainy" /></template>
