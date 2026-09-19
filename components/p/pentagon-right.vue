<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbg9o4ilr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbg9o4ilr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:pentagon-right" /></template>
