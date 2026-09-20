<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2807ybdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t2807ybdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:user-add" /></template>
