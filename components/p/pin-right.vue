<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkraz_b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hkraz_b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:pin-right" /></template>
