<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc0ak45iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cc0ak45iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-split-3x1-fill" /></template>
