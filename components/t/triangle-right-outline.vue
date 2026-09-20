<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8m9zlofw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x8m9zlofw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangle-right-outline" /></template>
