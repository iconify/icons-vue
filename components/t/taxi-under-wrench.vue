<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0g1-0_hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c0g1-0_hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:taxi-under-wrench" /></template>
