<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm4j6-dsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xm4j6-dsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:park-15" /></template>
