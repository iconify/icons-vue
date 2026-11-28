<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yae56xbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yae56xbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stopwatch" /></template>
