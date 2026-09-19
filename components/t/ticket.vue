<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pafp66bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pafp66bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:ticket" /></template>
