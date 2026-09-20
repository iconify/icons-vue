<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcxv4abex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcxv4abex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:sort-outline" /></template>
