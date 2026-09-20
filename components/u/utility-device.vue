<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3wuugj7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j3wuugj7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-device" /></template>
