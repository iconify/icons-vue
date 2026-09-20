<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2lnfbf4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l2lnfbf4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:r-dark" /></template>
