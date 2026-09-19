<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d635mcbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d635mcbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-information-circle" /></template>
