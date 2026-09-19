<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmi3i5bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="pmi3i5bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:steam" /></template>
