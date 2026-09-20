<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-ohdt99i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w-ohdt99i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:sun" /></template>
