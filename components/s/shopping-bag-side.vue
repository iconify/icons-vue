<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffkvz2bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffkvz2bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:shopping-bag-side" /></template>
