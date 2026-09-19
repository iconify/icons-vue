<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp03et8ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp03et8ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plane-up" /></template>
