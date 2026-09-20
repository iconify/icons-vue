<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvt68wnkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cvt68wnkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pizza" /></template>
