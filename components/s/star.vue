<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1g63mdyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1g63mdyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:star" /></template>
