<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cce-x1b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cce-x1b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:play-stroke-16" /></template>
