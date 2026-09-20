<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6cablbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f6cablbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:stop" /></template>
