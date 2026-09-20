<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-vp-bb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g-vp-bb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plug" /></template>
