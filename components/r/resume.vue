<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u702qhixj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u702qhixj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:resume" /></template>
