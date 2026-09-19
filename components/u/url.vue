<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvgrnpbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":680,"height":810};
const content = `<path class="kvgrnpbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:url" /></template>
