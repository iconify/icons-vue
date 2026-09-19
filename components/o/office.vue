<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7f7z9bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m7f7z9bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:office" /></template>
