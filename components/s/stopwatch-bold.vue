<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs9_h7bln.css';
import '../../css/n/ni31jpbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs9_h7bln"/><path class="ni31jpbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:stopwatch-bold" /></template>
