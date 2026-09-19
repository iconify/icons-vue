<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq0kuqbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pq0kuqbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pen-nib" /></template>
