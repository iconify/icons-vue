<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfh4p2bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lfh4p2bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pin-pad-with-rupee" /></template>
