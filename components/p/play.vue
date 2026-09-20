<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp8b6cmyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pp8b6cmyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:play" /></template>
