<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5mmyei8x.css';
import '../../css/o/obv-dzbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5mmyei8x secondary"/><path class="obv-dzbot primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-bevel-duo" /></template>
