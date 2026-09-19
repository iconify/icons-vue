<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr02l2t6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sr02l2t6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-stroke-16" /></template>
