<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqt_46bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nqt_46bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:watson" /></template>
