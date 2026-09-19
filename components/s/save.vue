<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko_cibb2i.css';
import '../../css/b/bkhiprxmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ko_cibb2i"/><path class="bkhiprxmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:save" /></template>
