<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni3djwbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ni3djwbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shipwreck-in-water" /></template>
