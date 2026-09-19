<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy99j9bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="cy99j9bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:money-bill-wave" /></template>
