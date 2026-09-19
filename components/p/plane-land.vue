<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc3hafbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc3hafbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:plane-land" /></template>
