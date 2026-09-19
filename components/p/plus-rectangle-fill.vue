<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0_yfrxyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y0_yfrxyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-rectangle-fill" /></template>
