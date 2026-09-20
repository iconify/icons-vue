<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh22y12ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rh22y12ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-xii" /></template>
