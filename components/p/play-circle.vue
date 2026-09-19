<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_anq_b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="a_anq_b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:play-circle" /></template>
