<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noi34ubfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="noi34ubfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:w-outline" /></template>
