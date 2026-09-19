<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxr63lbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gxr63lbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:tap" /></template>
