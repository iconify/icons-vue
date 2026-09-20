<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq2m70lut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xq2m70lut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sedan-with-raised-hood" /></template>
