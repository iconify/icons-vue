<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxyo3ya3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vxyo3ya3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-water" /></template>
