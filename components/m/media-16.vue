<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj2y_opli.css';
import '../../css/k/klmk3-lhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wj2y_opli"/><path clip-rule="evenodd" class="klmk3-lhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:media-16" /></template>
