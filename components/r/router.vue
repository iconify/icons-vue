<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj_y2v3db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pj_y2v3db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:router" /></template>
