<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2pgsccln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k2pgsccln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:square-outline-with-bottom-right-half" /></template>
