<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp0hb84pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zp0hb84pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-arrow-right" /></template>
