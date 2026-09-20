<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeme7nnhw.css';
import '../../css/y/yt3wrgl6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeme7nnhw"/><path class="yt3wrgl6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qingyan" /></template>
