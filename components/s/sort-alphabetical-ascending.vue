<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsd6y5yjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vsd6y5yjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sort-alphabetical-ascending" /></template>
