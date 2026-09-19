<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjwhhhtch.css';
import '../../css/j/j4m9ayhmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="xjwhhhtch"/><path class="j4m9ayhmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:torsos-female-male" /></template>
