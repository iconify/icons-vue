<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkovyh8fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkovyh8fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stop-circle" /></template>
