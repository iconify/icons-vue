<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klj372b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="klj372b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:stack-simple-plus-bold" /></template>
