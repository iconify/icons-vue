<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq8bm1t3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eq8bm1t3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:treasure-map-x" /></template>
