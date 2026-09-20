<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhv8_vmwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mhv8_vmwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:resize-smaller-16" /></template>
