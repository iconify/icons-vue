<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x39s_of4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1472};
const content = `<path class="x39s_of4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:profile" /></template>
