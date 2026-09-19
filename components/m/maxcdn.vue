<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r313nlbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":24};
const content = `<path class="r313nlbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:maxcdn" /></template>
