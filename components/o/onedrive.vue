<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0czi8bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u0czi8bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:onedrive" /></template>
