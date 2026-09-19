<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hixwd4_oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="hixwd4_oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:wpforms" /></template>
