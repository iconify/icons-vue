<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcpdy7bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dcpdy7bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:star-half" /></template>
