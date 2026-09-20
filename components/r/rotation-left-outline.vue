<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coai96h7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="coai96h7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:rotation-left-outline" /></template>
