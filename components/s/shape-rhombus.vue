<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqijryb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqijryb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:shape-rhombus" /></template>
