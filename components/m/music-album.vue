<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl_hn_bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jl_hn_bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:music-album" /></template>
