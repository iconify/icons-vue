<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbylo6bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="qbylo6bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:recycle" /></template>
