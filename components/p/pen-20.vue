<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azix1pzje.css';
import '../../css/j/jdmv1bb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="azix1pzje"/><path class="jdmv1bb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pen-20" /></template>
