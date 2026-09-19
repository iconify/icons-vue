<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub-dxdbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ub-dxdbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:windows" /></template>
