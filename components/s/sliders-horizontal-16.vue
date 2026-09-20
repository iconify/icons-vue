<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3cg6w9vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l3cg6w9vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sliders-horizontal-16" /></template>
