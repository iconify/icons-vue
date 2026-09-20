<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2r1fphfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w2r1fphfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:menorah" /></template>
