<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcmyc104n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lcmyc104n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:rock-bold" /></template>
