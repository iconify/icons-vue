<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqn50zb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqn50zb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:map-pin-off" /></template>
