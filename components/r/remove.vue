<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0w1dlbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="t0w1dlbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:remove" /></template>
