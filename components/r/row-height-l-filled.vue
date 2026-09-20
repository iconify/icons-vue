<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-1_xy66d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k-1_xy66d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:row-height-l-filled" /></template>
