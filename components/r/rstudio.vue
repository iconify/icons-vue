<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxjbt1vlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxjbt1vlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rstudio" /></template>
