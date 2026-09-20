<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4ekc_jgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d4ekc_jgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stone-wall" /></template>
