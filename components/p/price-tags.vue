<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp8c-eb8i.css';
import '../../css/h/hid2coqpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":16};
const content = `<path class="fp8c-eb8i"/><path class="hid2coqpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:price-tags" /></template>
