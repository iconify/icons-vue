<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe62bdcxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oe62bdcxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:russian-orthodox-cross" /></template>
