<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_2v8v8uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="i_2v8v8uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:palette-fill-12" /></template>
