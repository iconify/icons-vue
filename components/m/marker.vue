<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgs12i4vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zgs12i4vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:marker" /></template>
