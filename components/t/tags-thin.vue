<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_5bvnb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="s_5bvnb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:tags-thin" /></template>
