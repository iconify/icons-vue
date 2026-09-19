<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0x1nqbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s0x1nqbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:z-lpar" /></template>
