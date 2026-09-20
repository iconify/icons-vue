<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoba4e2xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zoba4e2xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:scribble-outline" /></template>
