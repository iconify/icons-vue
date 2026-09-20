<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwifwsllj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vwifwsllj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:seven-one-one" /></template>
