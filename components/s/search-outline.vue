<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs5ad85nx.css';
import '../../css/d/d6rwj94cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bs5ad85nx"/><path class="d6rwj94cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:search-outline" /></template>
