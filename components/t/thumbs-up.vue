<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj2v90w6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gj2v90w6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:thumbs-up" /></template>
