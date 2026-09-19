<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xocd9kbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="xocd9kbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:tent-1" /></template>
