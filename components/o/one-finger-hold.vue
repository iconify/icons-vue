<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqke4i0do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kqke4i0do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-finger-hold" /></template>
