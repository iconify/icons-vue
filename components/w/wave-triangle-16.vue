<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx-eucbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yx-eucbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wave-triangle-16" /></template>
