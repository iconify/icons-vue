<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc7pk4nsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jc7pk4nsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-chevrons-right" /></template>
