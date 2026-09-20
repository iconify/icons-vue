<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tznvg3blh.css';
import '../../css/g/gvyhpkbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tznvg3blh"/><path clip-rule="evenodd" class="gvyhpkbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:save-to-disk-16" /></template>
