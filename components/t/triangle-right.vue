<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9tkx_0qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l9tkx_0qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-right" /></template>
