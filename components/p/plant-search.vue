<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_iy0tb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="b_iy0tb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-search" /></template>
