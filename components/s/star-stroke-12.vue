<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn27sub2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rn27sub2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:star-stroke-12" /></template>
