<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bng7pxiak.css';
import '../../css/f/fpr969b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bng7pxiak"/><path class="fpr969b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:zipper-mouth" /></template>
