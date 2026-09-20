<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6m6xlb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="q6m6xlb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:movie-rental" /></template>
