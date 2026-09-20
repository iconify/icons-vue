<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8b4sjb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="q8b4sjb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:text" /></template>
