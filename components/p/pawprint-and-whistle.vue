<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvx1k5bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bvx1k5bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pawprint-and-whistle" /></template>
