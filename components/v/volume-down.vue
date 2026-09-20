<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pentrqbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pentrqbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:volume-down" /></template>
