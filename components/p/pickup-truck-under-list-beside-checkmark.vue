<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocvy942nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ocvy942nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-under-list-beside-checkmark" /></template>
