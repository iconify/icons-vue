<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw-vxn9lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jw-vxn9lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:windows" /></template>
