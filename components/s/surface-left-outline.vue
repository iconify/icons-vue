<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6lbg1bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p6lbg1bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:surface-left-outline" /></template>
