<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf5j1qb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wf5j1qb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-plus3" /></template>
