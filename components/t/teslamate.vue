<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prptthbtt.css';
import '../../css/z/zo-mdg_qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="prptthbtt"/><path class="zo-mdg_qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teslamate" /></template>
