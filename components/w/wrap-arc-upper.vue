<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsl9_-rus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rsl9_-rus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:wrap-arc-upper" /></template>
