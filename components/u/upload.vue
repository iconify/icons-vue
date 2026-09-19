<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuq3_flxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uuq3_flxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:upload" /></template>
