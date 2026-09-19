<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c74wu66qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c74wu66qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:search" /></template>
