<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luql266jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luql266jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shopping-music" /></template>
