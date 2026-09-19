<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgvh4kkig.css';
import '../../css/r/r5sqe9b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pgvh4kkig"/><path class="r5sqe9b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:storage" /></template>
