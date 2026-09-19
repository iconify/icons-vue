<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxqxepb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxqxepb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:play" /></template>
