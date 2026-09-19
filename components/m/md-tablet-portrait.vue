<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcdf_nbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gcdf_nbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-tablet-portrait" /></template>
