<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyzuv-nov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kyzuv-nov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:stack-simple-check-thin" /></template>
