<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbrcyl_dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":6,"height":16};
const content = `<path class="cbrcyl_dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-right" /></template>
