<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh5j54mvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh5j54mvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:size-uniform-filled" /></template>
