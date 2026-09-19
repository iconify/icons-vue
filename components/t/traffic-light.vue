<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on9_x8i1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="on9_x8i1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:traffic-light" /></template>
