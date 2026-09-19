<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr8u2x3pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mr8u2x3pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:right-arrow-circle" /></template>
