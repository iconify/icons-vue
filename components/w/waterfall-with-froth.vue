<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4pralb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u4pralb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:waterfall-with-froth" /></template>
