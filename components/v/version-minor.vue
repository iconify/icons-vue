<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg_xf-bjm.css';
import '../../css/s/stheyzbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bg_xf-bjm"/><path class="stheyzbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:version-minor" /></template>
