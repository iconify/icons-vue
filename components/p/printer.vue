<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1uu6_bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m1uu6_bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:printer" /></template>
