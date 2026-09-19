<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f19_pj4xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f19_pj4xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:music" /></template>
