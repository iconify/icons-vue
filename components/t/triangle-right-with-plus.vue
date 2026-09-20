<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp8jjlbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lp8jjlbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-right-with-plus" /></template>
