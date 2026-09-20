<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1a5awbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l1a5awbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:passport-with-bundesadler" /></template>
