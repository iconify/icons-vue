<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4nnf_b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r4nnf_b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:windows" /></template>
