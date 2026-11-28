<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzkqyibmp.css';
import '../../css/g/g768bfbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzkqyibmp secondary"/><path class="g768bfbwz primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mouse-pointer-duo" /></template>
