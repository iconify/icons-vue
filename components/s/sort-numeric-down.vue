<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj9qppsak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hj9qppsak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:sort-numeric-down" /></template>
