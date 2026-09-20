<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoyx8fb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xoyx8fb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:play-circle" /></template>
