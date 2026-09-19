<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx81x8bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="yx81x8bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mug-saucer" /></template>
