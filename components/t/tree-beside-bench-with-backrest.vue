<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1r1dsu7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x1r1dsu7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tree-beside-bench-with-backrest" /></template>
