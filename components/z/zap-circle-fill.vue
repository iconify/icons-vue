<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg7t42bnk.css';
import '../../css/u/ustelzbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg7t42bnk"/><path class="ustelzbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:zap-circle-fill" /></template>
