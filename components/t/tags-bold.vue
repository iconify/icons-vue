<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtr0n5b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dtr0n5b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:tags-bold" /></template>
