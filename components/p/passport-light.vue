<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2wbkcbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k2wbkcbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:passport-light" /></template>
