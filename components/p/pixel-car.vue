<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v_h1fdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c9v_h1fdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-car" /></template>
