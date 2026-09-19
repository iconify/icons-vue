<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wce5fjbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wce5fjbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:star" /></template>
