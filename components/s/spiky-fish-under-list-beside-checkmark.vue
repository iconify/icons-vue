<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5ny2v5ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r5ny2v5ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spiky-fish-under-list-beside-checkmark" /></template>
