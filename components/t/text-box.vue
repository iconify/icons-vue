<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmlm_3bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fmlm_3bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:text-box" /></template>
