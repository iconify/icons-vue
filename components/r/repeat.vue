<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5e6emb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5e6emb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:repeat" /></template>
