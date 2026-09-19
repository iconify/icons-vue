<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkj37haki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nkj37haki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:train-freight-front" /></template>
