<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwn7_2srg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gwn7_2srg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:taoist-14" /></template>
