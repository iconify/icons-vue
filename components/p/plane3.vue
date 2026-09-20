<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3pu9ei_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3pu9ei_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plane3" /></template>
