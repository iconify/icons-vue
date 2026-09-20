<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms14et43n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ms14et43n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wave-square-16" /></template>
