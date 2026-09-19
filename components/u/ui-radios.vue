<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxbt59n7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vxbt59n7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:ui-radios" /></template>
