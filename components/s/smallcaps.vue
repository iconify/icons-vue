<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2a793r0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2a793r0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smallcaps" /></template>
