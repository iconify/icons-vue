<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpl0q1bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="xpl0q1bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:volume-off" /></template>
