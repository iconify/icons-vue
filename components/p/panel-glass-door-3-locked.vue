<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddwa9ybpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddwa9ybpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door-3-locked" /></template>
