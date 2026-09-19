<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4_0get0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n4_0get0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spinner11" /></template>
