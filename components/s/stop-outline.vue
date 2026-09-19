<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b93j9cbjr.css';
import '../../css/d/dqndudb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b93j9cbjr"/><path class="dqndudb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stop-outline" /></template>
