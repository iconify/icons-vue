<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ba8lbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ba8lbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-down-04" /></template>
