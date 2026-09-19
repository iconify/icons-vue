<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5m0l1bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n5m0l1bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:threads" /></template>
