<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5_h21b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j5_h21b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play" /></template>
