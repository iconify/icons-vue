<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5bwus7zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f5bwus7zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:russian-cross" /></template>
