<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crh2c0bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="crh2c0bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:rotate-right" /></template>
