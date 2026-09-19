<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1e6-lqkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="j1e6-lqkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:nature-people" /></template>
