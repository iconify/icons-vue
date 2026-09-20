<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oam-6ybfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oam-6ybfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:trail-blaze" /></template>
