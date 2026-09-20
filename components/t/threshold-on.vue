<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzim9rbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lzim9rbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:threshold-on" /></template>
