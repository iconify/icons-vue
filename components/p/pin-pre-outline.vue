<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k330uibgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k330uibgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:pin-pre-outline" /></template>
