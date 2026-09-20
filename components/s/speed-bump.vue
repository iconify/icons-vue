<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qffx2xbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qffx2xbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:speed-bump" /></template>
