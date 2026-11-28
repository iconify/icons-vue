<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k775brneu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k775brneu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-wrap-thin" /></template>
