<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvf-sbcvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wvf-sbcvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sd-card-1" /></template>
