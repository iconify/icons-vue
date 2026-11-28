<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd_m2db3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bd_m2db3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:rock-tall-bold" /></template>
