<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr9h2wbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dr9h2wbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:one-two-three" /></template>
