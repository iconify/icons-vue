<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uct1ooplc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uct1ooplc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:resize" /></template>
