<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9s0-bc8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o9s0-bc8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:smiley-plus-light" /></template>
